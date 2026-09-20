<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd98yeb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fd98yeb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:warracker-dark" /></template>
