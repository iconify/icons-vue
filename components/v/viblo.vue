<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th3j_0vfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th3j_0vfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:viblo" /></template>
