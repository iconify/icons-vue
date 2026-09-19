<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iaw_6nhre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iaw_6nhre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:moustache" /></template>
