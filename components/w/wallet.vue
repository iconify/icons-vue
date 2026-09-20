<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3h9z2bfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3h9z2bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:wallet" /></template>
