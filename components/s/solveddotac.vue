<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz80rob8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz80rob8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:solveddotac" /></template>
