<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arfxhzlpu.css';
import '../../css/l/ludlzds-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="arfxhzlpu"/><path class="ludlzds-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:minimus" /></template>
