<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djtpkkswn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="djtpkkswn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:reactos" /></template>
