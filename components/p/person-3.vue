<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljycq4b6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ljycq4b6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:person-3" /></template>
