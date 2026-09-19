<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pld9fvbkz.css';
import '../../css/u/uvhrn1bbw.css';
import '../../css/n/nfquxfbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pld9fvbkz"/><path class="uvhrn1bbw"/><path class="nfquxfbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:squaredid" /></template>
