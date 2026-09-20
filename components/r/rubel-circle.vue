<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myf97jsmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="myf97jsmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:rubel-circle" /></template>
