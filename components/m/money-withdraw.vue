<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtcj7q16c.css';
import '../../css/y/yn4943o-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wtcj7q16c"/><path class="yn4943o-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:money-withdraw" /></template>
