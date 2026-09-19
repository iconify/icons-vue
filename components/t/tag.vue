<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvlspab7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvlspab7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:tag" /></template>
