<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y65eipb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y65eipb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:users" /></template>
