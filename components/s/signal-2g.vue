<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi71-2bem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi71-2bem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:signal-2g" /></template>
