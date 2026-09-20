<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bumpl1bqw.css';
import '../../css/h/hosfmobjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bumpl1bqw"/><path class="hosfmobjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:receipt-wrangler" /></template>
