<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlj2xmbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qlj2xmbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:moonwaxingcrescent" /></template>
