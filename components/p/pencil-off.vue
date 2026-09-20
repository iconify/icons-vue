<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so5y9pc7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so5y9pc7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pencil-off" /></template>
