<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h33ta5bij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h33ta5bij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:printer" /></template>
