<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sndhfs_uj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sndhfs_uj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:table-column-outline" /></template>
