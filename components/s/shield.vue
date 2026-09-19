<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_6e4bfxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_6e4bfxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:shield" /></template>
