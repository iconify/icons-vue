<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2sfk-bes.css';
import '../../css/a/ajxq6raqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j2sfk-bes"/><path class="ajxq6raqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:money" /></template>
