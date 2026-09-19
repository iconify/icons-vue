<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhjclqosn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vhjclqosn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:user-group-20-solid" /></template>
