<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mji2cccso.css';
import '../../css/q/q2jwsje5o.css';
import '../../css/x/x1yme9bxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mji2cccso"/><path class="q2jwsje5o"/><path class="x1yme9bxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:signal" /></template>
