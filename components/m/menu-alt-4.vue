<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/saz4hzcge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="saz4hzcge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:menu-alt-4" /></template>
