<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6td3jbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="c6td3jbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:user-follow-stroke-12" /></template>
