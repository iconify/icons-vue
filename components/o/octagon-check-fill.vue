<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh4vwnbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vh4vwnbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:octagon-check-fill" /></template>
