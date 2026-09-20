<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xke0zjbte.css';
import '../../css/i/itxo1tb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xke0zjbte"/><path class="itxo1tb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pillar" /></template>
