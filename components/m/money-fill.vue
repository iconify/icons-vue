<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owb0njbke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="owb0njbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:money-fill" /></template>
