<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iowo5oevp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="iowo5oevp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:rancher-wordmark" /></template>
