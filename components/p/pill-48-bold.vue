<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d16mu3fsh.css';
import '../../css/e/et91ikbvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d16mu3fsh"/><path class="et91ikbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pill-48-bold" /></template>
