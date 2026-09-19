<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-7-j98_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-7-j98_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wrist-watch-alt-filled" /></template>
