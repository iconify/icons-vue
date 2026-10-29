<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inj1tcbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inj1tcbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-circle-question-solid" /></template>
