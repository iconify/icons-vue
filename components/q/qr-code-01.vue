<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmz_-_bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmz_-_bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:qr-code-01" /></template>
