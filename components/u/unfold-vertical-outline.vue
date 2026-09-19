<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4egcmb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path clip-rule="evenodd" class="m4egcmb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:unfold-vertical-outline" /></template>
