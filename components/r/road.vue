<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8gp7h6jt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8gp7h6jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:road" /></template>
