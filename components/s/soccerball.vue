<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q58kriblw.css';
import '../../css/t/tc02e-b4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q58kriblw"/><path class="tc02e-b4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:soccerball" /></template>
