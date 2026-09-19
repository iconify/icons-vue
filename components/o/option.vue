<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1j9ghh7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1j9ghh7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:option" /></template>
