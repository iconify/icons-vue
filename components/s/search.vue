<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow0wjkqcp.css';
import '../../css/a/alyn96y6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ow0wjkqcp"/><path class="alyn96y6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:search" /></template>
