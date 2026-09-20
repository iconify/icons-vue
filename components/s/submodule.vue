<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd2khn9on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vd2khn9on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:submodule" /></template>
