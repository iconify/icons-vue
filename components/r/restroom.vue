<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4tskmdbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4tskmdbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:restroom" /></template>
