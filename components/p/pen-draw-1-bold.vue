<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bboc-fber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bboc-fber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:pen-draw-1-bold" /></template>
