<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs80a_qke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qs80a_qke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:search-normal2" /></template>
