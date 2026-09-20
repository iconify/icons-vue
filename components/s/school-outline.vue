<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3s8zzbno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p3s8zzbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:school-outline" /></template>
