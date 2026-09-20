<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwc7t8bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwc7t8bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:shirt-flat" /></template>
