<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d13k8pb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d13k8pb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:minus" /></template>
