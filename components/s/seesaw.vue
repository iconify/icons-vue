<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/burzc71_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="burzc71_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:seesaw" /></template>
