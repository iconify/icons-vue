<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmh_o2bqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jmh_o2bqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-library-filled" /></template>
