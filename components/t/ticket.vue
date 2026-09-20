<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju64m7nre.css';
import '../../css/g/gm7gmzfit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ju64m7nre"/><path class="gm7gmzfit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:ticket" /></template>
