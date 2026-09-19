<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukn8gvbzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukn8gvbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:move-01" /></template>
