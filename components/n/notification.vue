<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/b/bluheubuq.css';
import '../../css/k/kuv1vkb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(3 2)" class="jtowsomii"><path class="bluheubuq"/><circle class="kuv1vkb9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:notification" /></template>
