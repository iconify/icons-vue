<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emt7v4xbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-1.5};
const content = `<path class="emt7v4xbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:shield-minus-f" /></template>
