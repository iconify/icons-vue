<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2u665ban.css';
import '../../css/f/fo91v3b2u.css';
import '../../css/y/yh_orebxr.css';
import '../../css/b/bczv-dd1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="k2u665ban"><path class="fo91v3b2u"/><path clip-rule="evenodd" class="yh_orebxr"/><path class="bczv-dd1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:test-tube" /></template>
