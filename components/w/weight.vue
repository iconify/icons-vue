<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boq9-pb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="boq9-pb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:weight" /></template>
