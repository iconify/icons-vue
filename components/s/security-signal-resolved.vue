<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp-9wf2on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tp-9wf2on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:security-signal-resolved" /></template>
