<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl0oxmbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pl0oxmbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:society6" /></template>
