<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh4-yy1bi.css';
import '../../css/j/jnfyn9bda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fh4-yy1bi"/><path class="jnfyn9bda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mop-sparkles-filled" /></template>
