<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_xrf_70t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t_xrf_70t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:reel-filled" /></template>
