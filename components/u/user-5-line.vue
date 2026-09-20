<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5-kmbhbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5-kmbhbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-5-line" /></template>
