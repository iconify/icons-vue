<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fra1fsbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fra1fsbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:zoom-workplace" /></template>
