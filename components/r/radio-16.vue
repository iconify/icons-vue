<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygc0_0gjy.css';
import '../../css/e/e1lpwkvyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ygc0_0gjy"/><path clip-rule="evenodd" class="e1lpwkvyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:radio-16" /></template>
