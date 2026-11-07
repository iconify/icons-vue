<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl6wzybyg.css';
import '../../css/k/kvxqcabet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nl6wzybyg"/><path class="kvxqcabet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-bottom-open-bold" /></template>
