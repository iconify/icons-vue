<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/f/fv6k7p8vn.css';
import '../../css/t/tlzj7xbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="n1lsf0bnc"><path class="fv6k7p8vn"/><path class="tlzj7xbfp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:person-plus" /></template>
