<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzkr7cr_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rzkr7cr_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:wifi-signal-off" /></template>
