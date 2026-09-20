<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvf9z4y7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvf9z4y7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:navigation-fill" /></template>
