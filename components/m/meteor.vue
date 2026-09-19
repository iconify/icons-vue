<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/escl5q8dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="escl5q8dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:meteor" /></template>
