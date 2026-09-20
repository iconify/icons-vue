<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6wl880iz.css';
import '../../css/g/gzs8_jbiw.css';
import '../../css/i/i5vl1gfpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6wl880iz"/><path class="gzs8_jbiw"/><path class="i5vl1gfpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:object-group" /></template>
