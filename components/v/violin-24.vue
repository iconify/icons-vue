<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwxeveicl.css';
import '../../css/c/czx85ujqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwxeveicl"/><path class="czx85ujqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:violin-24" /></template>
