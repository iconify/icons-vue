<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsf314beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":512};
const content = `<path class="nsf314beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:ms-dos" /></template>
