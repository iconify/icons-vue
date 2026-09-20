<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghwh-4apg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ghwh-4apg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:resize-width" /></template>
