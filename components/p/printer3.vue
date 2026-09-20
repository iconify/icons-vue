<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p180r4b0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p180r4b0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:printer3" /></template>
