<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3jfgmbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n3jfgmbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:robot-vacuum-filled" /></template>
