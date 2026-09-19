<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxc2ifb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":31,"height":24};
const content = `<path class="wxc2ifb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:soundcloud" /></template>
