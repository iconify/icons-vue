<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/reuni_bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="reuni_bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:piano-filled" /></template>
