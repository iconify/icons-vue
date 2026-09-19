<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odyud6-1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="odyud6-1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:pokemon" /></template>
