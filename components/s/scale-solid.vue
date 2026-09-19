<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co2b8uqdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="co2b8uqdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:scale-solid" /></template>
