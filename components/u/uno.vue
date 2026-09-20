<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9dp65n1d.css';
import '../../css/t/tqpzs3bol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9dp65n1d"/><path class="tqpzs3bol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:uno" /></template>
