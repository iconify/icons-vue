<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0wuxkb3p.css';
import '../../css/s/s-8c-vb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d0wuxkb3p"/><path class="s-8c-vb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:picnic-48-bold" /></template>
