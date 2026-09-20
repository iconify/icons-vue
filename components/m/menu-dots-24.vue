<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1mk5dhbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1mk5dhbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:menu-dots-24" /></template>
