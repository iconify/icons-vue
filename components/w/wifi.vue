<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7a35wbsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7a35wbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:wifi" /></template>
