<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0vlgacxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0vlgacxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:quote-single-left-filled" /></template>
