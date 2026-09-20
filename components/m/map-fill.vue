<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8fcnxmjq.css';
import '../../css/c/cdkh7bjct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h8fcnxmjq"/><circle class="cdkh7bjct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:map-fill" /></template>
