<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjwz8ybnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjwz8ybnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mail-x" /></template>
