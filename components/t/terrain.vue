<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/peab942ah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="peab942ah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:terrain" /></template>
