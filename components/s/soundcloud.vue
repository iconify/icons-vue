<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4etpy67f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4etpy67f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:soundcloud" /></template>
