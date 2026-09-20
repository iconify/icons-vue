<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8vhdsbzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8vhdsbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:regroup-light" /></template>
