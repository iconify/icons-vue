<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/omm4qdoyz.css';
import '../../css/t/tphx6mb1h.css';
import '../../css/s/sb1if-bxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="omm4qdoyz"/><path class="tphx6mb1h"/><path class="sb1if-bxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:sponge" /></template>
