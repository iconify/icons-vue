<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfomdp99f.css';
import '../../css/c/clgt-tmqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<circle class="xfomdp99f"/><path class="clgt-tmqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:unisex" /></template>
