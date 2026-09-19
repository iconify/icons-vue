<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/e/euswu1aos.css';
import '../../css/r/r_ta68biz.css';
import '../../css/f/fn1_yeb0r.css';
import '../../css/k/k6fuj7c6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="euswu1aos"/><path class="r_ta68biz"/><path class="fn1_yeb0r"/><path class="k6fuj7c6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:timer-1-outline" /></template>
