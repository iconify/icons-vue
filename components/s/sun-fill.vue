<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zam0b_mmh.css';
import '../../css/i/i1d8z5cie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zam0b_mmh"/><path clip-rule="evenodd" class="i1d8z5cie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:sun-fill" /></template>
