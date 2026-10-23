<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjnb0cb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjnb0cb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:pointer-off" /></template>
