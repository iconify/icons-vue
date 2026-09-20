<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_now3vgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_now3vgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber-color:underline" /></template>
