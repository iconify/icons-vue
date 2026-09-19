<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6kyc2-vd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="a6kyc2-vd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:sc-twitter" /></template>
