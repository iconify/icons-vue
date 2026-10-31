<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arepo8bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arepo8bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square-letter-i" /></template>
