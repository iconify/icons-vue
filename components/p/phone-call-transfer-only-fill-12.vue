<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrzprmb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="nrzprmb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-call-transfer-only-fill-12" /></template>
