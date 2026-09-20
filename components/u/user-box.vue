<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/j/jq6j-7brw.css';
import '../../css/p/pwbt2qflx.css';
import '../../css/j/jgjjp7t-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="jq6j-7brw"/><circle class="pwbt2qflx"/><rect class="jgjjp7t-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:user-box" /></template>
