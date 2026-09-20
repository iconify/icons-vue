<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln7w7tbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ln7w7tbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:thangs" /></template>
