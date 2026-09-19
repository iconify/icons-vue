<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrb463bje.css';
import '../../css/a/a23i8nphm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jrb463bje"/><path class="a23i8nphm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:nonpotablewatersymbol" /></template>
