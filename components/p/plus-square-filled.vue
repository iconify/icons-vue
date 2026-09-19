<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w72ejob-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w72ejob-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:plus-square-filled" /></template>
