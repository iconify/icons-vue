<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbgxfd0gy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbgxfd0gy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:mail" /></template>
