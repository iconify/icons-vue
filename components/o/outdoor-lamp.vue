<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/geb8sxbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="geb8sxbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:outdoor-lamp" /></template>
