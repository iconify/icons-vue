<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af786g-gs.css';
import '../../css/t/tf51z5b-b.css';
import '../../css/e/e5y3liomb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af786g-gs"/><path class="tf51z5b-b"/><path class="e5y3liomb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rgen" /></template>
