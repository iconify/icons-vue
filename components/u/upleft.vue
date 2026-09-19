<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amf6q6f-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="amf6q6f-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:upleft" /></template>
