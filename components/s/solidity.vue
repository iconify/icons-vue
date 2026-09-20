<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/criho_qpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="criho_qpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:solidity" /></template>
