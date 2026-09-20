<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k82zlrxzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k82zlrxzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:operately-light" /></template>
