<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sue7ftw_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sue7ftw_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:move-to-end-24" /></template>
