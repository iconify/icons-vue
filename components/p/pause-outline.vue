<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9p3ynbre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p9p3ynbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:pause-outline" /></template>
