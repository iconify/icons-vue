<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl-87t-9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pl-87t-9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:trolleybus" /></template>
