<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beb66tbza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="beb66tbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:question-circle-fill" /></template>
