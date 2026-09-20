<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/limzqubuc.css';
import '../../css/a/ar6xy1boo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="limzqubuc"/><path class="ar6xy1boo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:user-heart" /></template>
