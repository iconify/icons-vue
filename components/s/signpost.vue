<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/graw_wnsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="graw_wnsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:signpost" /></template>
