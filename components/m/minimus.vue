<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arfxhzlpu.css';
import '../../css/o/oxu08acul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="arfxhzlpu"/><path class="oxu08acul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:minimus" /></template>
