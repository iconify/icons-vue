<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpdcd9hma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":832};
const content = `<path class="gpdcd9hma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:powerjack" /></template>
