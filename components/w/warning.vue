<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ice71tbrt.css';
import '../../css/w/wl50x4lxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ice71tbrt"/><path class="wl50x4lxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:warning" /></template>
