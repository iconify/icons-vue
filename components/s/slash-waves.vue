<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfk6ibbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfk6ibbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:slash-waves" /></template>
