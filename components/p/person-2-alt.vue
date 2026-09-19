<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk4bebj_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="vk4bebj_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:person-2-alt" /></template>
