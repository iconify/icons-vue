<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxc63y5rs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxc63y5rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ruby" /></template>
