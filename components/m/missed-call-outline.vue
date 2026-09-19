<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy31kfb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy31kfb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:missed-call-outline" /></template>
