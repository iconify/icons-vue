<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc6m-t-sq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc6m-t-sq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:twinmotion" /></template>
