<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9x-6rbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9x-6rbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:shield" /></template>
