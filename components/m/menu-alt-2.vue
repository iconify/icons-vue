<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxpmk7qmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="vxpmk7qmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:menu-alt-2" /></template>
