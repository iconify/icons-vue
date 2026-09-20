<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha-ru_sez.css';
import '../../css/z/zuyihimme.css';
import '../../css/o/ob81ctbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ha-ru_sez"/><path class="zuyihimme"/><path class="ob81ctbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sambanova" /></template>
