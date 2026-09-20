<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nme7svmcs.css';
import '../../css/f/fnrrisblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nme7svmcs"/><path class="fnrrisblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:options" /></template>
