<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnupiibrx.css';
import '../../css/z/zf2tkskut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bnupiibrx"/><path class="zf2tkskut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:pen-tool-filled" /></template>
