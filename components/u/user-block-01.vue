<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/byr5dkqie.css';
import '../../css/b/bbpve-yut.css';
import '../../css/s/s_ng-gbav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="byr5dkqie"/><circle class="bbpve-yut"/><path class="s_ng-gbav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:user-block-01" /></template>
