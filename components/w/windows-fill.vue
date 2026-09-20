<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6_l66cbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6_l66cbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:windows-fill" /></template>
