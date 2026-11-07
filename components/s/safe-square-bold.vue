<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycq6r6b3w.css';
import '../../css/a/a2habdbvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycq6r6b3w"/><path clip-rule="evenodd" class="a2habdbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:safe-square-bold" /></template>
