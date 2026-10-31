<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx264d-rm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tx264d-rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:train-gloss" /></template>
