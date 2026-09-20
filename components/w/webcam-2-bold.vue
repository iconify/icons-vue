<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cti6nxbgy.css';
import '../../css/k/kiyzhcvkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cti6nxbgy"/><path class="kiyzhcvkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:webcam-2-bold" /></template>
