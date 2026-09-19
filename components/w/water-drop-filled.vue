<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwcbthb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwcbthb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:water-drop-filled" /></template>
