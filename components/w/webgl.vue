<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7d-mk6up.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s7d-mk6up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:webgl" /></template>
