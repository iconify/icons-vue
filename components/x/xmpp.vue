<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx_27wbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tx_27wbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:xmpp" /></template>
