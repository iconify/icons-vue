<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyhrc7b4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gyhrc7b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:speedalt" /></template>
