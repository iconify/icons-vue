<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks-z6wb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks-z6wb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:p1s" /></template>
