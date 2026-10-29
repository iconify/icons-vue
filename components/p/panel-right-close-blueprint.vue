<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/c/ce8p3bcxi.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/j/jv-k-dbpo.css';
import '../../css/q/qxe4b7cgo.css';
import '../../css/o/o0frbhb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="ce8p3bcxi wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="jv-k-dbpo wm-k"/><path class="qxe4b7cgo wm-a"/><path class="o0frbhb7o wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:panel-right-close-blueprint" /></template>
