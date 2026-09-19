<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hex5etblr.css';
import '../../css/m/mfq_7cbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hex5etblr"/><path class="mfq_7cbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:palette" /></template>
