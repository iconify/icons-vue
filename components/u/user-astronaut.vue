<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aceq8mbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="aceq8mbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:user-astronaut" /></template>
