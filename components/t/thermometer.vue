<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvxzpacfj.css';
import '../../css/c/ct7sk1bjh.css';
import '../../css/q/q0_8skbgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvxzpacfj wm-k"/><path class="ct7sk1bjh wm-k"/><path class="q0_8skbgb wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:thermometer" /></template>
