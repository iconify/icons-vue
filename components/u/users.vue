<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv90j7b5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yv90j7b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:users" /></template>
