<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t45mdvb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t45mdvb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:stop-circle-solid" /></template>
