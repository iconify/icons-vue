<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b91wmnvdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b91wmnvdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:multimedia-controls-loop-arrow" /></template>
