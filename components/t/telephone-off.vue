<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktc0rob3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktc0rob3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:telephone-off" /></template>
