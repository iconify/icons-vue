<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z09i_33ng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z09i_33ng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pairdrop-dark" /></template>
