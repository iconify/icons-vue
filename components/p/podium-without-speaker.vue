<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2pno_a1u.css';
import '../../css/m/mp1ra6pzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u2pno_a1u"/><path class="mp1ra6pzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:podium-without-speaker" /></template>
