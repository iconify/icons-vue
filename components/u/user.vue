<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng-o3gbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng-o3gbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:user" /></template>
