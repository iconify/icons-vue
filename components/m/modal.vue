<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de9x37bdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de9x37bdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:modal" /></template>
