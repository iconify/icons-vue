<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7wtvsbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7wtvsbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:sigma" /></template>
