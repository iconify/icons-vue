<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbt_c7bwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pbt_c7bwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:polkadot-dot-fill" /></template>
