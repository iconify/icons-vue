<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4upji2kx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b4upji2kx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:zoom-out" /></template>
