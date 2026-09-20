<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht7vchbfw.css';
import '../../css/e/ek3qulhkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ht7vchbfw"/><path clip-rule="evenodd" class="ek3qulhkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:sort-time-asc-16" /></template>
