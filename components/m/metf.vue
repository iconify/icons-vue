<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/faye_bcvv.css';
import '../../css/d/dg6f8nblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="faye_bcvv"/><path clip-rule="evenodd" class="dg6f8nblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:metf" /></template>
