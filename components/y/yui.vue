<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt35k1b6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mt35k1b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:yui" /></template>
