<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph626sk7j.css';
import '../../css/p/p3y5o8bll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ph626sk7j"/><path class="p3y5o8bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mic-filled" /></template>
