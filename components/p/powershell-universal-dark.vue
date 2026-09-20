<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv640qtmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gv640qtmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:powershell-universal-dark" /></template>
