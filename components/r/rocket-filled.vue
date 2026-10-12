<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogx29lbfw.css';
import '../../css/a/azwen8bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogx29lbfw"/><path clip-rule="evenodd" class="azwen8bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:rocket-filled" /></template>
