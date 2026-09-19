<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1rtdfb3c.css';
import '../../css/u/uowjoqehi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1rtdfb3c"/><path class="uowjoqehi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:search-code" /></template>
