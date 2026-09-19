<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctkupt07p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ctkupt07p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:size-text-small-filled" /></template>
