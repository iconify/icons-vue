<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xomdi8b2s.css';
import '../../css/n/nuemgvbfx.css';
import '../../css/c/cc6_nwbfm.css';
import '../../css/d/db4425i8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="xomdi8b2s"/><path class="nuemgvbfx"/><path class="cc6_nwbfm"/><path class="db4425i8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:philippines" /></template>
