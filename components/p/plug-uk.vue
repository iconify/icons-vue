<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8c_s2h5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8c_s2h5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:plug-uk" /></template>
