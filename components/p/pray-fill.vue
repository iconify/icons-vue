<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glv3o6b_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="glv3o6b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pray-fill" /></template>
