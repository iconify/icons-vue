<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnbshjbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnbshjbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:riseup" /></template>
