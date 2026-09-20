<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da3zc1bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="da3zc1bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:time-fill" /></template>
