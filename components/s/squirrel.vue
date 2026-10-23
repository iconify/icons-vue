<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr8ti0b8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hr8ti0b8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:squirrel" /></template>
