<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6i-kbbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p6i-kbbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:nemerle" /></template>
