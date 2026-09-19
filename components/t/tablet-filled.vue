<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bojbs1zxp.css';
import '../../css/t/tuobqqwah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bojbs1zxp"/><path class="tuobqqwah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tablet-filled" /></template>
