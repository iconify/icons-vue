<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzjlihbdq.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/j/jomn23bik.css';
import '../../css/w/w0g0foxru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="lzjlihbdq"/><g class="jn8qy4bru"><path class="jomn23bik"/><path class="w0g0foxru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:shamrock" /></template>
