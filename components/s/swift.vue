<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq5h1pbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq5h1pbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:swift" /></template>
