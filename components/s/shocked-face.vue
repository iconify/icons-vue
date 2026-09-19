<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha7yqp6ru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ha7yqp6ru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:shocked-face" /></template>
