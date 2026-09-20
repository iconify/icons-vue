<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0ccmcb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="t0ccmcb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:more-horizontal-solid" /></template>
