<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0ucx7bbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0ucx7bbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:panels-right-bottom" /></template>
