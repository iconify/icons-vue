<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmae0kb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hmae0kb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:puzzle-piece" /></template>
