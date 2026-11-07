<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao23nccsy.css';
import '../../css/y/ye6llnqhf.css';
import '../../css/m/mzfoi9l1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao23nccsy"/><path class="ye6llnqhf"/><path clip-rule="evenodd" class="mzfoi9l1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:upload-square-outline" /></template>
