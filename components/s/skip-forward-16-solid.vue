<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irwkgeb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="irwkgeb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:skip-forward-16-solid" /></template>
