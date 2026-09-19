<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezijqjblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":778};
const content = `<path class="ezijqjblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:safari" /></template>
