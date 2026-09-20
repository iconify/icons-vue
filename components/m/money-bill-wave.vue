<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8b93bckm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j8b93bckm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:money-bill-wave" /></template>
