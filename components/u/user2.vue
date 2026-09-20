<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stwsl5b-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="stwsl5b-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user2" /></template>
