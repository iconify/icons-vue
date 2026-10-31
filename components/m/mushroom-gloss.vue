<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpz__0blq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpz__0blq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mushroom-gloss" /></template>
