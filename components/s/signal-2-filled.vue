<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm6gogb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm6gogb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:signal-2-filled" /></template>
