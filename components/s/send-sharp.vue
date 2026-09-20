<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/javbxgzww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="javbxgzww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:send-sharp" /></template>
