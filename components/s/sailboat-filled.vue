<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlx4kgb-m.css';
import '../../css/o/ogjjes7pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlx4kgb-m"/><path class="ogjjes7pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sailboat-filled" /></template>
