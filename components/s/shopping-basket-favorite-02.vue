<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/mtweo9b7w.css';
import '../../css/e/emjzqgb3y.css';
import '../../css/y/yjo9i5b3u.css';
import '../../css/x/xpbdn4bfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="mtweo9b7w"/><path class="emjzqgb3y"/><path class="yjo9i5b3u"/><path class="xpbdn4bfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shopping-basket-favorite-02" /></template>
