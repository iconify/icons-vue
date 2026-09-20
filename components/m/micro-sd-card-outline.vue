<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhwrucx5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bhwrucx5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:micro-sd-card-outline" /></template>
