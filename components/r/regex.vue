<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6ltadbch.css';
import '../../css/k/kr7x2fb8x.css';
import '../../css/s/st5q72b9l.css';
import '../../css/g/gbtrt9bem.css';
import '../../css/e/evqehct3f.css';
import '../../css/a/ag_y68byo.css';
import '../../css/e/erzet3b6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6ltadbch wm-shadow"/><path class="kr7x2fb8x wm-k"/><path class="st5q72b9l wm-k"/><path class="gbtrt9bem wm-k"/><path class="evqehct3f wm-k"/><path class="ag_y68byo wm-shine"/><path class="erzet3b6e wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:regex" /></template>
