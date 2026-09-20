<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs8qhvbzx.css';
import '../../css/m/mueojzrmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qs8qhvbzx"/><path class="mueojzrmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nforwardauth" /></template>
