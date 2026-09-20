<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzx-n9bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dzx-n9bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:thumbs-down-solid" /></template>
