<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cofw0c4re.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="cofw0c4re"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:sparkles" /></template>
