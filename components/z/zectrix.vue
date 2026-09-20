<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aoz36pb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aoz36pb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:zectrix" /></template>
