<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcadwc-xf.css';
import '../../css/k/kdwpv2bov.css';
import '../../css/a/a-z8z7pww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="rcadwc-xf"/><path class="kdwpv2bov"/><path class="a-z8z7pww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sortarr-light" /></template>
