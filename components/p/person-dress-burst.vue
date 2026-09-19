<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av5c-t6zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="av5c-t6zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:person-dress-burst" /></template>
