<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scjmdrbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scjmdrbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sticker-fill" /></template>
