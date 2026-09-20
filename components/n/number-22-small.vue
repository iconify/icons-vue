<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut7y1yr2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut7y1yr2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-22-small" /></template>
