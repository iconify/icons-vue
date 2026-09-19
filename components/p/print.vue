<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv3-k1ocu.css';
import '../../css/h/hxk53pb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xv3-k1ocu"/><path class="hxk53pb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:print" /></template>
