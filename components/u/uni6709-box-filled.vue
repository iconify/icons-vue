<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4al-jb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="k4al-jb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:uni6709-box-filled" /></template>
