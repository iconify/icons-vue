<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/airnd3bbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="airnd3bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:step-back-filled" /></template>
