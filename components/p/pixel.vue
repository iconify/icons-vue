<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgavekyxp.css';
import '../../css/b/bop73y1vi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgavekyxp"/><path class="bop73y1vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pixel" /></template>
