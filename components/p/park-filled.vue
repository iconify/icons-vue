<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6riji-tw.css';
import '../../css/t/t05fz5bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6riji-tw"/><path class="t05fz5bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:park-filled" /></template>
