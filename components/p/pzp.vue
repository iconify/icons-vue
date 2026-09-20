<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urnyzzbwd.css';
import '../../css/a/as20a8ocv.css';
import '../../css/m/m5m17-bys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urnyzzbwd"/><path class="as20a8ocv"/><path class="m5m17-bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pzp" /></template>
