<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os6uvc61m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":24};
const content = `<path class="os6uvc61m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:person" /></template>
