<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac9ldtb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ac9ldtb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:volume" /></template>
