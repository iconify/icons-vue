<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl2xf4b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zl2xf4b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:swatch-fill" /></template>
