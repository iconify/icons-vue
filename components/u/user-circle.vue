<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-60od0wj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-60od0wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:user-circle" /></template>
