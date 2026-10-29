<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjx4p748a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjx4p748a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:undo-solid" /></template>
