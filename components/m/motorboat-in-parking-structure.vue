<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/extgh2bog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="extgh2bog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorboat-in-parking-structure" /></template>
