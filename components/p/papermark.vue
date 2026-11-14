<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtf2h3l6b.css';
import '../../css/a/a61ltbq0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xtf2h3l6b"/><path class="a61ltbq0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:papermark" /></template>
