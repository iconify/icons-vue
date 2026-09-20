<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1dd95b3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o1dd95b3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:webgazer-dark" /></template>
