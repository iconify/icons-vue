<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf9g28u7s.css';
import '../../css/t/tbc_z2b1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sf9g28u7s"/><path class="tbc_z2b1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mouse-left-filled" /></template>
