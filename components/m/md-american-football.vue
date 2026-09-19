<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfbprr8-v.css';
import '../../css/r/rd41_2bru.css';
import '../../css/t/tllvccb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vfbprr8-v"/><path class="rd41_2bru"/><g><path class="tllvccb_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-american-football" /></template>
