<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj2v5po7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aj2v5po7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:shredder-solid" /></template>
