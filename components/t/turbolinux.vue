<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep5hu0tam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep5hu0tam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:turbolinux" /></template>
