<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ormpdu8ur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ormpdu8ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:rewind-right-outline" /></template>
