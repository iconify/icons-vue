<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu2zzwf5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":31,"height":24};
const content = `<path class="xu2zzwf5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:quote-a-right" /></template>
