<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk15v_fiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":766};
const content = `<path class="uk15v_fiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:zoomout" /></template>
