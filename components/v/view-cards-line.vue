<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfhqbtb_c.css';
import '../../css/n/nk6q6ee7e.css';
import '../../css/u/uos4js72w.css';
import '../../css/q/qzqgo1b-a.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 lfhqbtb_c"/><path class="clr-i-outline clr-i-outline-path-2 nk6q6ee7e"/><path class="clr-i-outline clr-i-outline-path-3 uos4js72w"/><path class="clr-i-outline clr-i-outline-path-4 qzqgo1b-a"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:view-cards-line" /></template>
