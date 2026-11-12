<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1d7chbrz.css';
import '../../css/q/qiyg0hb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="b1d7chbrz"/><path class="qiyg0hb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:punipuni" /></template>
