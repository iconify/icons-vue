<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwtif3bjl.css';
import '../../css/h/h02ib-6ed.css';
import '../../css/y/yjpow2b-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bwtif3bjl"/><path class="h02ib-6ed"/><path class="yjpow2b-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:markschaptersymbol" /></template>
