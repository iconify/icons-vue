<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3f1cdmin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="s3f1cdmin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:megaphone2x-outline" /></template>
