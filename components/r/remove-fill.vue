<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/derwdeb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="derwdeb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:remove-fill" /></template>
