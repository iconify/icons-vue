<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwk_e0oiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwk_e0oiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sun-moon-solid" /></template>
