<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olgj_vbqo.css';
import '../../css/f/f1syezbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olgj_vbqo"/><path clip-rule="evenodd" class="f1syezbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-up-bold-duotone" /></template>
