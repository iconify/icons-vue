<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1kq_5bdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1kq_5bdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:number-1" /></template>
