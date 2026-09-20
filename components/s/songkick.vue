<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phpjd9j4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phpjd9j4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:songkick" /></template>
