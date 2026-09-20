<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-w7kybcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p-w7kybcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:vase" /></template>
