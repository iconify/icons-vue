<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br5n2-bih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br5n2-bih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:plus-sm" /></template>
