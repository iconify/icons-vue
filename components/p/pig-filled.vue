<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hiq-huvyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hiq-huvyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pig-filled" /></template>
