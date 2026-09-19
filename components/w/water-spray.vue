<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydg7xpknt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydg7xpknt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:water-spray" /></template>
