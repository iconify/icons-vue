<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr6nkx0mi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr6nkx0mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shape" /></template>
