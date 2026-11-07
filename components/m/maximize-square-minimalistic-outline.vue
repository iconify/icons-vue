<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8h-3cbpv.css';
import '../../css/j/jr-ln5z8r.css';
import '../../css/t/t5k-_f5ou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8h-3cbpv"/><path class="jr-ln5z8r"/><path clip-rule="evenodd" class="t5k-_f5ou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:maximize-square-minimalistic-outline" /></template>
