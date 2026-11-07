<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm03gzbnp.css';
import '../../css/d/d-g40esoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path class="d-g40esoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-square-bold-duotone" /></template>
