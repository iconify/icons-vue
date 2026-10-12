<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txfdyr9af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txfdyr9af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-filled" /></template>
