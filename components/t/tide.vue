<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u21fx_xji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u21fx_xji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:tide" /></template>
