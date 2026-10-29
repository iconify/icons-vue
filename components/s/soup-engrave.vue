<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/n3eggmokr.css';
import '../../css/u/ubh6k1bby.css';
import '../../css/e/eyza0v3jg.css';
import '../../css/a/aedlnnets.css';
import '../../css/g/g0jhk334h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="n3eggmokr wm-k"/><path class="ubh6k1bby wm-a"/><path class="eyza0v3jg wm-shadow"/><path class="aedlnnets wm-k"/><path class="g0jhk334h wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:soup-engrave" /></template>
