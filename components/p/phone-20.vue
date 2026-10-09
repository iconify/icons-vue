<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzvr72bgj.css';
import '../../css/b/bn3wwcchr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mzvr72bgj"/><path class="bn3wwcchr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:phone-20" /></template>
