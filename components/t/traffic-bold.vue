<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk6nt8boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nk6nt8boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:traffic-bold" /></template>
