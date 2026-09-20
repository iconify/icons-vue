<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc72tnbzk.css';
import '../../css/i/i3fanzlul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fc72tnbzk"/><path class="i3fanzlul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rootstock" /></template>
