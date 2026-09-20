<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txj5poo9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txj5poo9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:reply-sharp" /></template>
