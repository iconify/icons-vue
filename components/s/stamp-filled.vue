<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-7shwbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-7shwbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:stamp-filled" /></template>
