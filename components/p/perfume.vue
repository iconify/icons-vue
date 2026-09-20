<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_0ssjbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z_0ssjbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:perfume" /></template>
