<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9datvxfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h9datvxfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:sidebar-right-16-solid" /></template>
