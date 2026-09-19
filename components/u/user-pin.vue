<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll-p0ub7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll-p0ub7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:user-pin" /></template>
