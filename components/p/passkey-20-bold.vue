<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsi2vccmn.css';
import '../../css/f/fjxpc8spu.css';
import '../../css/r/re2dj7mko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bsi2vccmn"/><path class="fjxpc8spu"/><path class="re2dj7mko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:passkey-20-bold" /></template>
