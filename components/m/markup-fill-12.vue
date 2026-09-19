<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bowbitjld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="bowbitjld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:markup-fill-12" /></template>
