<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzx8i8ica.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bzx8i8ica"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pickup-truck" /></template>
