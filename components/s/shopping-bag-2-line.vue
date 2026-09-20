<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avt3a6b-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avt3a6b-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shopping-bag-2-line" /></template>
