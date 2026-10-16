<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kscfdx84i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kscfdx84i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:moonrise-48" /></template>
