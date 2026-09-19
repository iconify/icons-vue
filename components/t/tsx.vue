<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhke-gbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mhke-gbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:tsx" /></template>
