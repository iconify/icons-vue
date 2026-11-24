<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-2jtuy5b.css';
import '../../css/i/iuh-1_bkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-2jtuy5b"/><path clip-rule="evenodd" class="iuh-1_bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tv-minimal-play-filled" /></template>
