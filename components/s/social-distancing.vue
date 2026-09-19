<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt9xz1bki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tt9xz1bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:social-distancing" /></template>
