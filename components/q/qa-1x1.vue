<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8nalnb6j.css';
import '../../css/z/z89mqybmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o8nalnb6j"/><path class="z89mqybmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:qa-1x1" /></template>
