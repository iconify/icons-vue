<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxa8a0btp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxa8a0btp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:scrum-alliance" /></template>
