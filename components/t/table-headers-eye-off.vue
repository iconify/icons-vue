<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k534gcbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k534gcbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-headers-eye-off" /></template>
