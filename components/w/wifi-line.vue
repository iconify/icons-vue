<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plkbd4s3q.css';
import '../../css/t/t-j9pcchv.css';
import '../../css/v/vfdjhe3si.css';
import '../../css/f/fs9da2b6b.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 plkbd4s3q"/><path class="clr-i-outline clr-i-outline-path-2 t-j9pcchv"/><path class="clr-i-outline clr-i-outline-path-3 vfdjhe3si"/><path class="clr-i-outline clr-i-outline-path-4 fs9da2b6b"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:wifi-line" /></template>
