<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_k3o6i9g.css';
import '../../css/v/vpv8vrdpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u_k3o6i9g"/><path class="vpv8vrdpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:voidauth-light" /></template>
