<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjnta2jlp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yjnta2jlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user" /></template>
