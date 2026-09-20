<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z47l6_8sb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z47l6_8sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:picpay" /></template>
