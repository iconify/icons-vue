<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnl_fybld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnl_fybld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:unfold-horizontal-fill" /></template>
