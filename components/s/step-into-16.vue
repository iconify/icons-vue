<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e39j9zbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e39j9zbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:step-into-16" /></template>
