<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts1sl1b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ts1sl1b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:sd-card-outline" /></template>
