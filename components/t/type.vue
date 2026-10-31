<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/t/ty2upabki.css';
import '../../css/a/a-zbi3bjx.css';
import '../../css/i/i5lay3b9t.css';
import '../../css/b/bbz2ti0md.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="ty2upabki wm-shadow"/><path class="a-zbi3bjx wm-shadow"/><path class="i5lay3b9t"/><path class="bbz2ti0md"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:type" /></template>
