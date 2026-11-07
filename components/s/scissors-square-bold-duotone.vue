<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm03gzbnp.css';
import '../../css/a/am0b8ab3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path class="am0b8ab3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:scissors-square-bold-duotone" /></template>
