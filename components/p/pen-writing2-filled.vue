<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_0m1je2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_0m1je2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pen-writing2-filled" /></template>
