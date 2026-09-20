<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exv1xebfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="exv1xebfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:message-text-alt-outline" /></template>
