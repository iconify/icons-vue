<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0kmyjwhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0kmyjwhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:otk" /></template>
