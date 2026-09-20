<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emfpa0b7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="emfpa0b7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:ski-jumping" /></template>
