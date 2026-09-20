<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozyzan.css';
import '../../css/d/d-zrqjti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozyzan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:play-filled-to-pause-transition" /></template>
