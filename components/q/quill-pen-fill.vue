<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfhmpvbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfhmpvbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:quill-pen-fill" /></template>
