<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmibc4bxr.css';
import '../../css/f/fn6nz5b1f.css';
import '../../css/i/i5k9fornz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="nmibc4bxr"/><path class="fn6nz5b1f"/><path class="i5k9fornz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:northern-cyprus" /></template>
