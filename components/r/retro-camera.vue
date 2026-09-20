<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bji8i1b_f.css';
import '../../css/z/z-imr2beg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bji8i1b_f"/><path class="z-imr2beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:retro-camera" /></template>
