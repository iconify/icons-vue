<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy13uwzff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uy13uwzff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ton" /></template>
