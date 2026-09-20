<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvnfzn9zr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lvnfzn9zr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:optopia" /></template>
