<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/rrkjydeid.css';
import '../../css/c/clhe63_8r.css';
import '../../css/w/w2ixxib2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="rrkjydeid"/><path class="clhe63_8r"/><path class="w2ixxib2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:tabs" /></template>
