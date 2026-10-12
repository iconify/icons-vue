<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu9cqub2t.css';
import '../../css/u/uusba_vxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu9cqub2t"/><path class="uusba_vxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:speech-filled" /></template>
