<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/i/ilbeybc2v.css';
import '../../css/a/aqhok2bbj.css';
import '../../css/p/purz4ubxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="ilbeybc2v"/><circle class="aqhok2bbj"/><path class="purz4ubxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:mining-device-outline" /></template>
