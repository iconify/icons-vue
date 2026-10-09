<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufsgr437u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ufsgr437u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-cog-20" /></template>
