<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak21erbzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":768};
const content = `<path class="ak21erbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:visa" /></template>
