<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzerpnb0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="dzerpnb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:winter-mahjong" /></template>
