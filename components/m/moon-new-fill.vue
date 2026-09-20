<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsn627f2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zsn627f2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:moon-new-fill" /></template>
