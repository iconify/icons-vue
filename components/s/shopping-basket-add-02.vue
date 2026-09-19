<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/n/nm63zg0wp.css';
import '../../css/y/yjo9i5b3u.css';
import '../../css/d/dgznyouyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="nm63zg0wp"/><path class="yjo9i5b3u"/><path class="dgznyouyl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shopping-basket-add-02" /></template>
