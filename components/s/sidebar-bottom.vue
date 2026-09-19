<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/eau2_14yj.css';
import '../../css/h/hvkfyv_fw.css';
import '../../css/i/i5uwpy6kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="eau2_14yj"/><path class="hvkfyv_fw"/><path class="i5uwpy6kl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sidebar-bottom" /></template>
