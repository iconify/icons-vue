<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm7qjnegn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qm7qjnegn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:minus" /></template>
