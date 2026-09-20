<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c11d1wxjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c11d1wxjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:toolbox-outline" /></template>
