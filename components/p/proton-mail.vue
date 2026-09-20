<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmn5w0e9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmn5w0e9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:proton-mail" /></template>
