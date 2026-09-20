<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4-wcftdv.css';
import '../../css/x/x4rg6acqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4-wcftdv"/><path clip-rule="evenodd" class="x4rg6acqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ousd" /></template>
