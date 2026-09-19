<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7o_ndblm.css';
import '../../css/o/okqxufbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p7o_ndblm"/><path class="okqxufbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-cafe" /></template>
