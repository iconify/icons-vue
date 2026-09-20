<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4i84ebmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b4i84ebmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:sidebar-right-16-solid" /></template>
