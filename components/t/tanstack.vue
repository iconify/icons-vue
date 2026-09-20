<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw2pvyd_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hw2pvyd_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:tanstack" /></template>
