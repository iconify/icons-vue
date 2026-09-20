<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea74s5vdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea74s5vdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:user-edit" /></template>
