<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3nrppbry.css';
import '../../css/q/q7w59bb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="x3nrppbry"/><path class="q7w59bb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:sweden" /></template>
