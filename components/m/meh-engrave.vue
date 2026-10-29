<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/y_dfk98ko.css';
import '../../css/d/ddwgo19qw.css';
import '../../css/y/yw4fz_b6b.css';
import '../../css/b/b_cv058cj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k y_dfk98ko"/><path class="ddwgo19qw wm-shadow"/><path class="wm-k yw4fz_b6b"/><path class="b_cv058cj wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:meh-engrave" /></template>
