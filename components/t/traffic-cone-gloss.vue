<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur-iyhbir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ur-iyhbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:traffic-cone-gloss" /></template>
