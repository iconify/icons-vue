<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8fpg0bpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="h8fpg0bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:sigma" /></template>
