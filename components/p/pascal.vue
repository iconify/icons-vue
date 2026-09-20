<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf2yv3b4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kf2yv3b4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:pascal" /></template>
