<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulw0feb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulw0feb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:video-slash-filled" /></template>
