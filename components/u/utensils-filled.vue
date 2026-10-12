<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi8rx-aqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi8rx-aqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:utensils-filled" /></template>
