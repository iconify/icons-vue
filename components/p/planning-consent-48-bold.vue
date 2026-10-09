<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frd-8-btx.css';
import '../../css/n/ngqac4bpf.css';
import '../../css/y/y9mg2tbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="frd-8-btx"/><path class="ngqac4bpf"/><path class="y9mg2tbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:planning-consent-48-bold" /></template>
