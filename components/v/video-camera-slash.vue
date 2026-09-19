<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vugi_ac-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vugi_ac-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:video-camera-slash" /></template>
