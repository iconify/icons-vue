<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w15nws47s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w15nws47s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:phone-x" /></template>
