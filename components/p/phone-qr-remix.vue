<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh_l-jx2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fh_l-jx2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:phone-qr-remix" /></template>
