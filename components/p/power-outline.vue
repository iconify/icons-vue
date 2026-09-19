<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/f/f8nkb8g-f.css';
import '../../css/q/qyj6jnh_w.css';
import '../../css/n/nvj328b0o.css';
import '../../css/p/pwa5qqbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="f8nkb8g-f"/><path class="qyj6jnh_w"/><path class="nvj328b0o"/><path class="pwa5qqbfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:power-outline" /></template>
