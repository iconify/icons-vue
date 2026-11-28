<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdtza1b_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdtza1b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:phone-x" /></template>
