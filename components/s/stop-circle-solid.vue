<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm7b_gbkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="sm7b_gbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:stop-circle-solid" /></template>
