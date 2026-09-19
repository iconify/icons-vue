<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/odcwkzu6r.css';
import '../../css/o/ogasd1kpl.css';
import '../../css/a/aldr43bry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="odcwkzu6r"/><path class="ogasd1kpl"/><path class="aldr43bry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:subtract-duo" /></template>
