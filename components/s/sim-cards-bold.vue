<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxkkglg1b.css';
import '../../css/n/n32zpyb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxkkglg1b"/><path clip-rule="evenodd" class="n32zpyb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sim-cards-bold" /></template>
