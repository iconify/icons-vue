<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta5wkcqyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ta5wkcqyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:parking-fill" /></template>
