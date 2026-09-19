<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g83c24bxt.css';
import '../../css/p/p-cf1ibat.css';
import '../../css/a/agqgkbe7m.css';
import '../../css/l/l4rb_ediz.css';
import '../../css/f/foo0o5a-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="g83c24bxt"/><path clip-rule="evenodd" class="p-cf1ibat"/><path class="agqgkbe7m"/><path clip-rule="evenodd" class="l4rb_ediz"/><path class="foo0o5a-g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tachometer-1-outline" /></template>
