<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqcjrr7fx.css';
import '../../css/q/q77si10cw.css';
import '../../css/v/vco9mxxbz.css';
import '../../css/c/c721j6aor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqcjrr7fx"/><path class="q77si10cw"/><path class="vco9mxxbz"/><path class="c721j6aor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:polypad" /></template>
