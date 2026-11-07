<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl66i7bqg.css';
import '../../css/x/x-5f2htjo.css';
import '../../css/x/xa2k-bcvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="cl66i7bqg"/><path class="x-5f2htjo"/><path class="xa2k-bcvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimalistic-magnifier-zoom-in-bold-duotone" /></template>
