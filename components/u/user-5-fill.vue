<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhmp2zy9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhmp2zy9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-5-fill" /></template>
