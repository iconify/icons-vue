<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2g90nbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2g90nbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:uptobox" /></template>
