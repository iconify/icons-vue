<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjldq36og.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjldq36og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:path2" /></template>
