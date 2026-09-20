<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak3isib6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ak3isib6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:prio-high" /></template>
