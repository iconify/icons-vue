<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shtvigbaj.css';
import '../../css/t/td9yfnbnw.css';
import '../../css/q/ql028qbli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="shtvigbaj"/><path class="td9yfnbnw"/><path class="ql028qbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tvdb" /></template>
