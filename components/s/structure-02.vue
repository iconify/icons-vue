<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jsk1cskcf.css';
import '../../css/s/spnb3cbwy.css';
import '../../css/k/kpvc2fb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="jsk1cskcf"/><path class="spnb3cbwy"/><path class="kpvc2fb7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:structure-02" /></template>
