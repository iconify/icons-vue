<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1gnk_b4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n1gnk_b4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:server-cloud" /></template>
