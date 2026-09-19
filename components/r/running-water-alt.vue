<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynr6deb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ynr6deb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:running-water-alt" /></template>
