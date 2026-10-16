<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg4v4ywuk.css';
import '../../css/g/ghmmfobwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eg4v4ywuk"/><path class="ghmmfobwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:workflow-20-bold" /></template>
