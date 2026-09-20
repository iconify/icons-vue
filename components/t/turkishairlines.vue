<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okz34ybum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okz34ybum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:turkishairlines" /></template>
