<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vru8ler2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="vru8ler2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:person-swimming" /></template>
