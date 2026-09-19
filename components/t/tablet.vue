<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga5axac9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":560,"height":850};
const content = `<path class="ga5axac9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:tablet" /></template>
