<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4d1cib_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4d1cib_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:users-lock" /></template>
