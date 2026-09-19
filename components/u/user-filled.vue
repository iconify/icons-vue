<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7y10vixf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7y10vixf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:user-filled" /></template>
