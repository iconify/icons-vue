<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxqh5fbli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="lxqh5fbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:speech-balloon-heart-small-filled" /></template>
