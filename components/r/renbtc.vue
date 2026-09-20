<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wetsv3agd.css';
import '../../css/q/quihcfbar.css';
import '../../css/k/k8agsabod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wetsv3agd"/><path clip-rule="evenodd" class="quihcfbar"/><path class="k8agsabod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:renbtc" /></template>
