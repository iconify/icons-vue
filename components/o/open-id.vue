<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scoxq5b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="scoxq5b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:open-id" /></template>
