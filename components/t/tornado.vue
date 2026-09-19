<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/u/u5h9wfb1s.css';
import '../../css/b/bsnl8abfb.css';
import '../../css/s/s9ym1bbnq.css';
import '../../css/k/ky_n--5tp.css';
import '../../css/a/a5nfr3bks.css';
import '../../css/b/bzes-obux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="u5h9wfb1s"/><path class="bsnl8abfb"/><path class="s9ym1bbnq"/><path class="ky_n--5tp"/><path class="a5nfr3bks"/><path class="bzes-obux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tornado" /></template>
