<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngr20bcbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngr20bcbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:twitter" /></template>
