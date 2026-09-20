<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1rmevb5d.css';
import '../../css/s/sa9ni4pvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w1rmevb5d"/><path class="sa9ni4pvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:newspaper" /></template>
