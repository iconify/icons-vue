<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojp5e3b6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojp5e3b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:unitedairlines" /></template>
