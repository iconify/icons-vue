<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-ldyt6dl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-ldyt6dl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:plane-off-solid" /></template>
