<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff3cyt8fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ff3cyt8fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:skateboard-48-bold" /></template>
