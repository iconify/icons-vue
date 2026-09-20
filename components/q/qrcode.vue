<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbyvh60wm.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/av3m8fbrw.css';
import '../../css/d/da976vbvv.css';
import '../../css/f/fjfvtrkwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGczrnudJR" class="jbyvh60wm"/></defs><g class="ft5dv1b6b"><use href="#SVGczrnudJR"/><g class="av3m8fbrw"><use href="#SVGczrnudJR"/><path class="da976vbvv"/></g><path class="fjfvtrkwl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:qrcode" /></template>
