<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnj89bbgy.css';
import '../../css/z/z1_dpab3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnj89bbgy"/><path clip-rule="evenodd" class="z1_dpab3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifier-zoom-in-bold" /></template>
