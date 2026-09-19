<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx488obmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mx488obmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:openai" /></template>
