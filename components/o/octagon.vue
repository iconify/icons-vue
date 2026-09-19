<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epp-53c7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="epp-53c7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:octagon" /></template>
