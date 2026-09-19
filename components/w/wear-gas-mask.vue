<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct192wbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct192wbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:wear-gas-mask" /></template>
