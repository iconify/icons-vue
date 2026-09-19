<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl69ehb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kl69ehb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-2-square-fill" /></template>
