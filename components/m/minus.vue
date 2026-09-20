<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn9mlm2hc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn9mlm2hc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:minus" /></template>
