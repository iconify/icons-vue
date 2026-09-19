<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi0tphd-c.css';
import '../../css/h/h1r_1vbuz.css';
import '../../css/r/rhfe71a6y.css';
import '../../css/e/exh1ppbgt.css';
import '../../css/r/r6xfiyb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="zi0tphd-c"/><path class="h1r_1vbuz"/><path class="rhfe71a6y"/><path class="exh1ppbgt"/><path class="r6xfiyb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:monkey" /></template>
