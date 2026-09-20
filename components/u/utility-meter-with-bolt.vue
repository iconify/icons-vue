<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qustj7cbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qustj7cbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:utility-meter-with-bolt" /></template>
