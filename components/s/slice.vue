<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4it59bup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4it59bup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:slice" /></template>
