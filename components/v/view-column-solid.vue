<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmnwzpb0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="wmnwzpb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:view-column-solid" /></template>
