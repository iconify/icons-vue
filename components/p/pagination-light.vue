<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/w/w6_b8q_9v.css';
import '../../css/r/rvuj5tb-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="w6_b8q_9v"/><rect class="rvuj5tb-l"/><rect class="rvuj5tb-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:pagination-light" /></template>
