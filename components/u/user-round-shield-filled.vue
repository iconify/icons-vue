<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4qkawp1w.css';
import '../../css/w/woy2hk4bh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4qkawp1w"/><path class="woy2hk4bh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-round-shield-filled" /></template>
