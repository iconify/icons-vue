<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkl6re2ft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tkl6re2ft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:menu-oreos" /></template>
