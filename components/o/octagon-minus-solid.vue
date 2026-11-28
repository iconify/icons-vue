<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqph13jba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqph13jba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:octagon-minus-solid" /></template>
