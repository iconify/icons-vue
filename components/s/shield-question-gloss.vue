<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs20kkbjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs20kkbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shield-question-gloss" /></template>
