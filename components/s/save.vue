<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykg_7cotr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykg_7cotr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:save" /></template>
