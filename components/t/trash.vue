<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gur7w6b5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gur7w6b5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:trash" /></template>
