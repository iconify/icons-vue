<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm3dcyb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm3dcyb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:txt" /></template>
