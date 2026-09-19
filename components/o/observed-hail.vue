<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrndicbcc.css';
import '../../css/s/s6jez3btv.css';
import '../../css/s/s31t99skb.css';
import '../../css/p/pvk172brt.css';
import '../../css/m/mxjh6ab9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mrndicbcc"/><circle class="s6jez3btv"/><circle class="s31t99skb"/><circle class="pvk172brt"/><path class="mxjh6ab9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:observed-hail" /></template>
