<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs-davxbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bs-davxbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:road-alt-light" /></template>
