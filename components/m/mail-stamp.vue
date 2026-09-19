<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eicjl9sjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":448};
const content = `<path class="eicjl9sjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:mail-stamp" /></template>
