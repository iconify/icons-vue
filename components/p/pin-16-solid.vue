<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv3i7l7nl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tv3i7l7nl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:pin-16-solid" /></template>
