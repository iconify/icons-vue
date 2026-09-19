<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqxr4wbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nqxr4wbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:upload-circle" /></template>
