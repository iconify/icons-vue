<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni6jdebub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ni6jdebub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:money-bill-alt" /></template>
