<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrxw13bgw.css';
import '../../css/c/c6a7psbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrxw13bgw"/><circle class="c6a7psbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:purchase-tag-alt" /></template>
