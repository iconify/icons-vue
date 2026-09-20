<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s__vy8qom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s__vy8qom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:washer2" /></template>
