<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb9ltdbub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":520,"height":654};
const content = `<path class="wb9ltdbub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:z" /></template>
