<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn_frcb-c.css';
import '../../css/n/n9_kl16fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jn_frcb-c"/><path clip-rule="evenodd" class="n9_kl16fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:socket-bold-duotone" /></template>
