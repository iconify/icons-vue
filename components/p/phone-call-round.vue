<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a55xm8bls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a55xm8bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-call-round" /></template>
