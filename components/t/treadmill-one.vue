<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btx30rb9t.css';
import '../../css/f/fezu9jvay.css';
import '../../css/a/a4tcz4b4u.css';
import '../../css/u/ukcu5rbys.css';
import '../../css/w/wefwctbsn.css';
import '../../css/b/bsvsyqvtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="btx30rb9t"><path class="fezu9jvay"/><path class="a4tcz4b4u"/><path class="ukcu5rbys"/><path class="wefwctbsn"/><path class="bsvsyqvtx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:treadmill-one" /></template>
