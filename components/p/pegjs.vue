<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjdjq9uaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":417,"height":512};
const content = `<path class="jjdjq9uaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:pegjs" /></template>
