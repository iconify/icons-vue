<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7irjcjwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7irjcjwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:octagon" /></template>
