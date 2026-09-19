<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk2t5mbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="yk2t5mbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:shuffle-arrows" /></template>
