<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl6ziybmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl6ziybmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sd-card-filled" /></template>
