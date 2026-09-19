<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce5e-7uxo.css';
import '../../css/g/gkgbpvxpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ce5e-7uxo"/><path class="gkgbpvxpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-construct" /></template>
