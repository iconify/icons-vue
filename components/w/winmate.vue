<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsxj7eb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zsxj7eb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:winmate" /></template>
