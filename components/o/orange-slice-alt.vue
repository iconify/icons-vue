<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugv8qvw0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugv8qvw0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:orange-slice-alt" /></template>
