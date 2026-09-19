<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu7p_-bky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hu7p_-bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:spinner" /></template>
