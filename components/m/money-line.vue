<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gru_1vbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gru_1vbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:money-line" /></template>
