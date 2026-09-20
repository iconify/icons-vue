<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmjtdybdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wmjtdybdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:thumbs-up-hand-with-sleeve" /></template>
