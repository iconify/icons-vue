<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcwt0vxow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcwt0vxow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:margin-left" /></template>
