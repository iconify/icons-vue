<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veaxrgwgs.css';
import '../../css/o/op-da8bcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="veaxrgwgs"/><path clip-rule="evenodd" class="op-da8bcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-pilcrow-filled" /></template>
