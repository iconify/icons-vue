<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqzmw3r4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqzmw3r4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:nfc" /></template>
