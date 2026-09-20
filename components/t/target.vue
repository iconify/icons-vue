<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2-ggdbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2-ggdbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:target" /></template>
