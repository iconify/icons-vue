<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6alihb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q6alihb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:safe-circle" /></template>
