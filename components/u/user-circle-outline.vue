<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnb8lgb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnb8lgb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:user-circle-outline" /></template>
