<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di7y9flmv.css';
import '../../css/t/tsepx-fqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="di7y9flmv"/><path class="tsepx-fqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:phrase-sentiment" /></template>
