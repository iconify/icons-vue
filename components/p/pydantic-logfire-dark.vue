<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwfl1bc9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bwfl1bc9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pydantic-logfire-dark" /></template>
