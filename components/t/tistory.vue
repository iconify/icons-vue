<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzs57dbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzs57dbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tistory" /></template>
