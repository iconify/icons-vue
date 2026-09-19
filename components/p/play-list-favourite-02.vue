<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/qia2bntri.css';
import '../../css/i/izs9_e8rp.css';
import '../../css/e/eyx_5_biz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="qia2bntri"/><path class="izs9_e8rp"/><path class="eyx_5_biz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:play-list-favourite-02" /></template>
