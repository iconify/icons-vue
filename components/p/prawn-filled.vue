<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr0d2hbau.css';
import '../../css/m/myu93rbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr0d2hbau"/><path class="myu93rbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:prawn-filled" /></template>
