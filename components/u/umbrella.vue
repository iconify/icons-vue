<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8cg_fa7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8cg_fa7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:umbrella" /></template>
