<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9khp6ncv.css';
import '../../css/m/m6xypubal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y9khp6ncv"/><path class="m6xypubal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:window-restore" /></template>
