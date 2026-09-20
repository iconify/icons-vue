<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf70drn3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf70drn3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ticktick" /></template>
