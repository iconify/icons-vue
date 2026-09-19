<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oaqxgfbxx.css';
import '../../css/s/sb3_ircqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oaqxgfbxx"/><path class="sb3_ircqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:save" /></template>
