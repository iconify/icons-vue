<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgc2aw0_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kgc2aw0_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:undo-alt" /></template>
