<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfyep0bnp.css';
import '../../css/a/a8ubjjxwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cfyep0bnp"/><path class="a8ubjjxwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:mobile-phone" /></template>
