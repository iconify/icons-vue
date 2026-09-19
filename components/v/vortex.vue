<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3cn6cc3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v3cn6cc3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:vortex" /></template>
