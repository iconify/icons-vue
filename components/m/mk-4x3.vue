<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/maggq5byx.css';
import '../../css/p/ph-tdvwvh.css';
import '../../css/d/dz9auwwmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="maggq5byx"/><path class="ph-tdvwvh"/><circle class="dz9auwwmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:mk-4x3" /></template>
