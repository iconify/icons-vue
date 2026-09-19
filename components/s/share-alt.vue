<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj4h_4poq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uj4h_4poq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:share-alt" /></template>
