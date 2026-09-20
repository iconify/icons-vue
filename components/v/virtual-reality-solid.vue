<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpyezrbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kpyezrbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:virtual-reality-solid" /></template>
