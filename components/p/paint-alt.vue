<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf6rg8q0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jf6rg8q0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:paint-alt" /></template>
