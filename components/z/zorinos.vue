<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkd5ofbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tkd5ofbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:zorinos" /></template>
