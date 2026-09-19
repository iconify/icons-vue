<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs-5ptelt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="bs-5ptelt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:person-2-square-stack-fill" /></template>
