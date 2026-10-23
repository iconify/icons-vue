<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn84l-der.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fn84l-der"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:send" /></template>
