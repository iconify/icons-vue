<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dx4nfqbec.css';
import '../../css/s/sbg6umb9z.css';
import '../../css/z/z6jpfcbpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dx4nfqbec"/><path class="sbg6umb9z"/><path class="z6jpfcbpc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:megaphone-off" /></template>
