<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh1s3ih8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hh1s3ih8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:shield-plus" /></template>
