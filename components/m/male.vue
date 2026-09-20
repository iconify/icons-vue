<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dogu1ji5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2.5,"top":-2.5};
const content = `<path class="dogu1ji5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:male" /></template>
