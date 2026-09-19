<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg9h-rbgi.css';
import '../../css/h/hnwh_8bzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="jg9h-rbgi"/><circle class="hnwh_8bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="geo:turf-along" /></template>
