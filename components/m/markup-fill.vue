<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g07yztbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g07yztbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:markup-fill" /></template>
