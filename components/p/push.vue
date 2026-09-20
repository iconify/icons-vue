<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3twlpavd.css';
import '../../css/e/eztzo_ccz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k3twlpavd"/><path class="eztzo_ccz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:push" /></template>
