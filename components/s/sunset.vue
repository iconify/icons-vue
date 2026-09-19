<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc8jj7o6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oc8jj7o6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:sunset" /></template>
