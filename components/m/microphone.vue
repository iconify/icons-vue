<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcag2xb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lcag2xb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:microphone" /></template>
