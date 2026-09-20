<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idi-7cb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="idi-7cb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vscode-fill" /></template>
