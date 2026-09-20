<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyefmbdcw.css';
import '../../css/f/fc0n3k16d.css';
import '../../css/u/utv6qqbkb.css';
import '../../css/w/whkqkbbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="cyefmbdcw"/><circle class="fc0n3k16d"/><circle class="utv6qqbkb"/><circle class="whkqkbbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:mushroom" /></template>
