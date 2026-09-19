<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dms1fbzlt.css';
import '../../css/r/rxjk7ymwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dms1fbzlt"/><path class="rxjk7ymwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:raisedhandpartfingers" /></template>
