<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4yu1bgbf.css';
import '../../css/j/jo-ewmbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4yu1bgbf"/><path class="jo-ewmbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:printer" /></template>
