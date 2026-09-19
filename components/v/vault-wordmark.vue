<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw6_0n11d.css';
import '../../css/o/okn9x2b2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="uw6_0n11d"/><path class="okn9x2b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:vault-wordmark" /></template>
