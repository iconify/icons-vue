<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixr5g_bgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixr5g_bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:traffic-barrier" /></template>
