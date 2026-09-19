<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4lt3lb1x.css';
import '../../css/i/i6r1xobqq.css';
import '../../css/e/e2kroochg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b4lt3lb1x"/><path class="i6r1xobqq"/><path class="e2kroochg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:opticaldiscicon" /></template>
