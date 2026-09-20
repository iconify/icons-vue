<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooxg0mb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ooxg0mb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:swagger" /></template>
