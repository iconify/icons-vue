<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwf8dez8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwf8dez8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-3-light" /></template>
