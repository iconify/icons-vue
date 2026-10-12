<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za_ktldbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="za_ktldbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-square-48-bold" /></template>
