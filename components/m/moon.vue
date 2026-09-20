<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st58rebqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="st58rebqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:moon" /></template>
