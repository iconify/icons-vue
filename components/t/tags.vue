<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g65aevbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g65aevbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:tags" /></template>
