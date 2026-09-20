<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz2639j6g.css';
import '../../css/r/rulnoebmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lz2639j6g"/><path class="rulnoebmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proton-mail-bridge-light" /></template>
