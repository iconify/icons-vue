<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2o3sh-9c.css';
import '../../css/k/kq38ase1a.css';
import '../../css/y/ypclhjnqv.css';
import '../../css/u/uaycyrbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<defs><path id="SVG3CSwIdnl" class="m2o3sh-9c"/></defs><path class="kq38ase1a"/><path class="ypclhjnqv"/><path class="clr-i-alert uaycyrbmu"/><use href="#SVG3CSwIdnl"/><use href="#SVG3CSwIdnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:map-outline-alerted" /></template>
