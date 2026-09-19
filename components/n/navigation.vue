<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de78-xbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de78-xbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:navigation" /></template>
