<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_hs9s_lv.css';
import '../../css/n/nikou0bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_hs9s_lv"/><path class="nikou0bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:phone-missed-call-fill" /></template>
