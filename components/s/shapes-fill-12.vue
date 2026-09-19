<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgg4whj9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zgg4whj9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:shapes-fill-12" /></template>
