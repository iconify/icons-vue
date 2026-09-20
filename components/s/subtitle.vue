<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyxq9bb-b.css';
import '../../css/r/r6p1cia5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pyxq9bb-b"/><path clip-rule="evenodd" class="r6p1cia5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:subtitle" /></template>
