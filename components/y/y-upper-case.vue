<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii_t20l9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":524,"height":735};
const content = `<path class="ii_t20l9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:y-upper-case" /></template>
