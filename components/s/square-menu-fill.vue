<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_86rhx9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_86rhx9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-menu-fill" /></template>
