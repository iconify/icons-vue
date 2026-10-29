<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g17mdac6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g17mdac6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:play" /></template>
