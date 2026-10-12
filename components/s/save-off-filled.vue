<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxm7zcclr.css';
import '../../css/s/sk2-r8bwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xxm7zcclr"/><path class="sk2-r8bwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:save-off-filled" /></template>
