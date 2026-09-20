<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmt-5dbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="cmt-5dbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:mongodb-solid" /></template>
