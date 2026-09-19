<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-atscb1d.css';
import '../../css/f/flmcfydke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g-atscb1d"/><path class="flmcfydke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:wallet-solid" /></template>
