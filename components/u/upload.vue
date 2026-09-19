<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lymv1xkrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lymv1xkrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:upload" /></template>
