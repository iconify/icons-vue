<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv_svdbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yv_svdbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:panasonic" /></template>
