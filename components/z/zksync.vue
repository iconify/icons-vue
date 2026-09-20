<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up82r_blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="up82r_blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:zksync" /></template>
