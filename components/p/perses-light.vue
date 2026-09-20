<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iivb983tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iivb983tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:perses-light" /></template>
