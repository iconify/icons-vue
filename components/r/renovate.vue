<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jndqku9wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jndqku9wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:renovate" /></template>
