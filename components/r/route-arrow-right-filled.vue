<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8z6jub6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8z6jub6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:route-arrow-right-filled" /></template>
