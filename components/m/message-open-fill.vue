<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebmufml3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ebmufml3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:message-open-fill" /></template>
