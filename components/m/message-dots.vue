<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krn2xfzde.css';
import '../../css/c/cg7d2pfom.css';
import '../../css/r/r_d7t_bew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krn2xfzde"/><circle class="cg7d2pfom"/><circle class="r_d7t_bew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:message-dots" /></template>
