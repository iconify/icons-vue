<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgariqbhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgariqbhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:underline" /></template>
