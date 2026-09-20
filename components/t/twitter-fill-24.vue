<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohs9pi70i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohs9pi70i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:twitter-fill-24" /></template>
