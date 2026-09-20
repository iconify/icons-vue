<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfe2xo-6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mfe2xo-6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:wrap-arch-solid" /></template>
