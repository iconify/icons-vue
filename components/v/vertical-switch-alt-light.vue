<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as0b5j_bf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="as0b5j_bf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:vertical-switch-alt-light" /></template>
