<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bkdjn0tvw.css';
import '../../css/y/yc5srhlrk.css';
import '../../css/e/eqo2hkbmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bkdjn0tvw"/><path class="yc5srhlrk"/><path class="eqo2hkbmw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:mortarboard-alt-light" /></template>
