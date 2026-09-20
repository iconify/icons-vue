<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyq1n69xz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyq1n69xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:wheelchair-alt" /></template>
