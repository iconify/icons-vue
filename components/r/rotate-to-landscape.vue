<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jewwt-x9z.css';
import '../../css/j/j02m59mzy.css';
import '../../css/c/cy0djhbhr.css';
import '../../css/h/htogyc_on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jewwt-x9z"/><path class="j02m59mzy"/><path class="cy0djhbhr"/><path class="htogyc_on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:rotate-to-landscape" /></template>
