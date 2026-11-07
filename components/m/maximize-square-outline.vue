<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp4du0pdy.css';
import '../../css/t/t5k-_f5ou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vp4du0pdy"/><path clip-rule="evenodd" class="t5k-_f5ou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:maximize-square-outline" /></template>
