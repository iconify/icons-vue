<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbqtq-4ae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbqtq-4ae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:roundcube" /></template>
