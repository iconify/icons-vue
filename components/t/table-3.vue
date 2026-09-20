<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o23j82g8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o23j82g8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:table-3" /></template>
