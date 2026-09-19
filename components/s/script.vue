<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjp8ftb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fjp8ftb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:script" /></template>
