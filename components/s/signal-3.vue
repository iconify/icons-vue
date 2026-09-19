<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yefjflajf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yefjflajf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:signal-3" /></template>
