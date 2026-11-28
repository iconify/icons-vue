<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apz4wh5li.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apz4wh5li"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:signpost" /></template>
