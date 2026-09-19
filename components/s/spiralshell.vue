<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufom-nbao.css';
import '../../css/n/nm31ulbpm.css';
import '../../css/c/cfg6-7biq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ufom-nbao"/><path class="nm31ulbpm"/><path class="cfg6-7biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:spiralshell" /></template>
