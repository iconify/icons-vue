<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af9zx_-vp.css';
import '../../css/x/xderynbbj.css';
import '../../css/o/oc-35l-aj.css';
import '../../css/o/ovvqimvbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="af9zx_-vp"/><path class="xderynbbj"/><path class="oc-35l-aj"/><path class="ovvqimvbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:react-16" /></template>
