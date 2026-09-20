<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj3iep4cf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj3iep4cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:powerautomate" /></template>
