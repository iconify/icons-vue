<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w52p69j0s.css';
import '../../css/g/gka2riira.css';
import '../../css/t/tt5riew3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="w52p69j0s"/><path class="gka2riira"/><path class="tt5riew3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:pineapple" /></template>
