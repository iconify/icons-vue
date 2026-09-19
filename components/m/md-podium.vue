<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ara2u6bia.css';
import '../../css/g/g1ssb8box.css';
import '../../css/p/ps_nwu9ub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ara2u6bia"/><path class="g1ssb8box"/><path class="ps_nwu9ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-podium" /></template>
