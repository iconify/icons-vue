<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc3az4b4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="jc3az4b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:speaker-2" /></template>
