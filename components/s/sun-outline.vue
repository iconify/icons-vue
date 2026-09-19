<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auouaz90v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="auouaz90v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:sun-outline" /></template>
