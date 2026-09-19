<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkehcvu9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkehcvu9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:signal-slash" /></template>
