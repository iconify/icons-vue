<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa4i_ynuq.css';
import '../../css/q/qfxk42bpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa4i_ynuq"/><path class="qfxk42bpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:messages-square-filled" /></template>
