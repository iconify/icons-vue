<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc_6r3r6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kc_6r3r6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:tea-cup-solid" /></template>
