<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psd7cpyss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="psd7cpyss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sofi-light" /></template>
