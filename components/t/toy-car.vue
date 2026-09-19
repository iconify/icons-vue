<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkn6c9j5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkn6c9j5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:toy-car" /></template>
