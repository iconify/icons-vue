<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4llw0bfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4llw0bfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:unlock" /></template>
