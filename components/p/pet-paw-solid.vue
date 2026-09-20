<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb-db-d4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tb-db-d4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:pet-paw-solid" /></template>
