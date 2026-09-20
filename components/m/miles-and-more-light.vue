<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5h4zjbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e5h4zjbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:miles-and-more-light" /></template>
