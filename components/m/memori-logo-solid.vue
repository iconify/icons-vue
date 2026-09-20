<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef7nkodfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ef7nkodfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:memori-logo-solid" /></template>
