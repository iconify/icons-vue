<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6fddvbdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6fddvbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:outline" /></template>
