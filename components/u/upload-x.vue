<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-dzk2ygk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-dzk2ygk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:upload-x" /></template>
