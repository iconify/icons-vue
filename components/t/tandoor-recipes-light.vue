<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq_6glbsc.css';
import '../../css/k/k2e-tqo9l.css';
import '../../css/y/ysphp0b9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wq_6glbsc"/><path class="k2e-tqo9l"/><path class="ysphp0b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tandoor-recipes-light" /></template>
