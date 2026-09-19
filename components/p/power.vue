<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-px0kjof.css';
import '../../css/h/h_xc7ccwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-px0kjof"/><path class="h_xc7ccwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:power" /></template>
