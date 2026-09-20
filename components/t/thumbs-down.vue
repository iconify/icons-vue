<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avjfuep5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avjfuep5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:thumbs-down" /></template>
