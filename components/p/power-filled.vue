<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rotxfmb0f.css';
import '../../css/e/ekbk75bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rotxfmb0f"/><path class="ekbk75bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:power-filled" /></template>
