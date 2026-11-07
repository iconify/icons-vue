<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft_uoeb3f.css';
import '../../css/m/mzfoi9l1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft_uoeb3f"/><path clip-rule="evenodd" class="mzfoi9l1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:undo-left-round-square-outline" /></template>
