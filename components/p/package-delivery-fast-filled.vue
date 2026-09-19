<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcncn6tkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rcncn6tkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:package-delivery-fast-filled" /></template>
