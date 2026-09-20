<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miu2v2oim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="miu2v2oim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:split" /></template>
