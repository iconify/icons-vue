<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm1ax3iyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm1ax3iyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:navigation-one" /></template>
