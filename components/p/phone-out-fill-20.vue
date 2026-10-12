<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myys72pto.css';
import '../../css/v/vk89q7biw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="myys72pto"/><path class="vk89q7biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-out-fill-20" /></template>
