<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g45c17bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g45c17bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:u-s-bank-dark" /></template>
