<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7atwzbzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7atwzbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:text-firstline-left" /></template>
