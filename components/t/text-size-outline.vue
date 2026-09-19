<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfiwejbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfiwejbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:text-size-outline" /></template>
