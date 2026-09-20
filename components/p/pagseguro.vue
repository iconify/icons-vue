<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mado7ibni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mado7ibni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:pagseguro" /></template>
