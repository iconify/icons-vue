<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/k80kg2mvy.css';
import '../../css/o/o_xxtf8jm.css';
import '../../css/p/p397vciec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="k80kg2mvy"/><path class="o_xxtf8jm"/><path class="p397vciec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:walking-line-duotone" /></template>
