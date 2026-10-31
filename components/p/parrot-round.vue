<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzlsxdblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzlsxdblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:parrot-round" /></template>
