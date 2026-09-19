<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg062c9yd.css';
import '../../css/w/w4rah7bzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rg062c9yd"/><path clip-rule="evenodd" class="w4rah7bzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:mining-pool-filled" /></template>
