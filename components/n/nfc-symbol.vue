<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqwhcbc2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="fqwhcbc2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:nfc-symbol" /></template>
