<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/lx0uz-bqb.css';
import '../../css/y/yjo9i5b3u.css';
import '../../css/w/wjr_4_bgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="lx0uz-bqb"/><path class="yjo9i5b3u"/><path class="wjr_4_bgf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shopping-basket-remove-02" /></template>
