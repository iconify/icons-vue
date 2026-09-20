<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js4f3kb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="js4f3kb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:sad-square-solid" /></template>
