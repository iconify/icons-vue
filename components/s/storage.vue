<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq3bjyb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="qq3bjyb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:storage" /></template>
