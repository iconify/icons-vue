<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9n5u8bdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9n5u8bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sick-fill" /></template>
