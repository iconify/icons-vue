<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z96m-mn-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z96m-mn-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:skip-previous-fill" /></template>
