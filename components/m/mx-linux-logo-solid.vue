<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4hjnqbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x4hjnqbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:mx-linux-logo-solid" /></template>
