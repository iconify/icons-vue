<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxly0_vhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qxly0_vhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:user-circle-star-light" /></template>
