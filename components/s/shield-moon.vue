<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_7jr7bkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_7jr7bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-moon" /></template>
