<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcbtmzz0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bcbtmzz0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:meh" /></template>
