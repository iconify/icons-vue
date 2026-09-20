<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4q04908s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z4q04908s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:users-outline" /></template>
