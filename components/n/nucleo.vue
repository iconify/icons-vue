<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayi46kkzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayi46kkzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:nucleo" /></template>
