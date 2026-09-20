<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exscprmgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exscprmgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:wallet-alt-line" /></template>
