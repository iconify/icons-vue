<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfs6ffbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfs6ffbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:user-add-outline" /></template>
