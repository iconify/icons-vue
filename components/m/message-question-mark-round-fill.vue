<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx450s6ch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx450s6ch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:message-question-mark-round-fill" /></template>
