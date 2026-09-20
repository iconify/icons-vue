<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e35kyaccs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e35kyaccs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:polkadot" /></template>
