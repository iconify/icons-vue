<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/drnrbe-2t.css';
import '../../css/t/t7cr3_k7i.css';
import '../../css/c/c_zsa6bia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="drnrbe-2t"/><path class="t7cr3_k7i"/><path class="c_zsa6bia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:orbit-02" /></template>
