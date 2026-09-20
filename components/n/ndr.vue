<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i60kh150c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i60kh150c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ndr" /></template>
