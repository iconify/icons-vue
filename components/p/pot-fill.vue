<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk1yj6bvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sk1yj6bvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pot-fill" /></template>
