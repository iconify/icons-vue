<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvq_hx_ln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nvq_hx_ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opensuse-light" /></template>
