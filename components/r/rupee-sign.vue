<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne0nl4bnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ne0nl4bnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:rupee-sign" /></template>
