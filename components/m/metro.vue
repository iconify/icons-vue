<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im0wz2aiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im0wz2aiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:metro" /></template>
