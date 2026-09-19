<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjwv7hjvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjwv7hjvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:store" /></template>
