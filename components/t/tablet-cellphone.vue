<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1q02n5hx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1q02n5hx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tablet-cellphone" /></template>
