<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nekqfff0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nekqfff0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:phone" /></template>
