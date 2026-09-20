<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvhg3tb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvhg3tb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:unlink-sharp-fill" /></template>
