<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk7v8qlqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk7v8qlqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rotate-right-05" /></template>
