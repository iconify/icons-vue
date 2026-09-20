<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lalxt3bxq.css';
import '../../css/t/tsc0xqbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lalxt3bxq"/><path class="tsc0xqbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:real-debrid" /></template>
