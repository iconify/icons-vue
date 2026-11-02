<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdw_0vb0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdw_0vb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tree-line" /></template>
