<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnb90nbxf.css';
import '../../css/s/sp3f8uwqx.css';
import '../../css/w/we9_13rpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnb90nbxf"/><path class="sp3f8uwqx"/><path class="we9_13rpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rewind-forward-circle-bold-duotone" /></template>
