<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi067zb2o.css';
import '../../css/v/vrgmnk6vg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mi067zb2o"/><path class="vrgmnk6vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:repo-forked-locked-16" /></template>
